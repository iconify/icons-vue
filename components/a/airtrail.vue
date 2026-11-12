<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyyohs43y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jyyohs43y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:airtrail" /></template>
