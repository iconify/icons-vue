<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpi02u7-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpi02u7-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bars-3-bottom-center" /></template>
