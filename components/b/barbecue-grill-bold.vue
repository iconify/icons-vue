<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nga6i44tb.css';
import '../../css/r/r7yb4cbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nga6i44tb"/><path class="r7yb4cbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:barbecue-grill-bold" /></template>
