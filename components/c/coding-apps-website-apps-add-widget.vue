<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgdcv4r6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgdcv4r6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:coding-apps-website-apps-add-widget" /></template>
