<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibs7ghb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ibs7ghb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:donut" /></template>
