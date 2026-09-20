<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7sufsb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7sufsb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-50" /></template>
