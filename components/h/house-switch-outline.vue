<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiih3sb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiih3sb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-switch-outline" /></template>
