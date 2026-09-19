<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfomjtbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hfomjtbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:arrows-pointing-in" /></template>
