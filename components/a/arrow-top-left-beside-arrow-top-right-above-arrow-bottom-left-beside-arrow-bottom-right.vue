<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hknlbeg7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hknlbeg7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-top-left-beside-arrow-top-right-above-arrow-bottom-left-beside-arrow-bottom-right" /></template>
