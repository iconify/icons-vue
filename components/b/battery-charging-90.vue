<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm2a5nb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm2a5nb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-90" /></template>
