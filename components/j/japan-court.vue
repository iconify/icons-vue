<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umulztzhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="umulztzhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:japan-court" /></template>
