<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk693vblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wk693vblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:layout-dashboard-thin" /></template>
