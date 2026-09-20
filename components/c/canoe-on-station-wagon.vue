<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k203-ju_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k203-ju_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:canoe-on-station-wagon" /></template>
