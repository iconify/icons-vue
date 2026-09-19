<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sckmimb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sckmimb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-down-left-square" /></template>
