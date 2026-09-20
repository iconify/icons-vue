<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crkp0tb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="crkp0tb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:frame" /></template>
