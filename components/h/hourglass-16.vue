<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pobd2gbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pobd2gbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:hourglass-16" /></template>
