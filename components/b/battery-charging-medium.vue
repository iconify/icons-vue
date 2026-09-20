<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkawnrb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkawnrb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-medium" /></template>
