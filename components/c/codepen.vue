<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me7di4b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="me7di4b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:codepen" /></template>
