<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw_r_-5rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tw_r_-5rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:hexagon-fill" /></template>
