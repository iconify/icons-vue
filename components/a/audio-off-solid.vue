<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjw983qia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wjw983qia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:audio-off-solid" /></template>
