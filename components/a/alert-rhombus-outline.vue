<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvlvdy-0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvlvdy-0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alert-rhombus-outline" /></template>
