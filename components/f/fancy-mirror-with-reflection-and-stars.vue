<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc26uubtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uc26uubtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fancy-mirror-with-reflection-and-stars" /></template>
