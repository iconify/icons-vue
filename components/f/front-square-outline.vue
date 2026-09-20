<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y05r1sudp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y05r1sudp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:front-square-outline" /></template>
