<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhy03hbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhy03hbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:drag-variant" /></template>
