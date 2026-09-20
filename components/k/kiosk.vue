<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0q2lackj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u0q2lackj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:kiosk" /></template>
