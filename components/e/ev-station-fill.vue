<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lio3y5lbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lio3y5lbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:ev-station-fill" /></template>
