<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy9xt0pmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vy9xt0pmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:flag" /></template>
