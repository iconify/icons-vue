<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e97trkb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e97trkb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bowling-pin-top-right" /></template>
