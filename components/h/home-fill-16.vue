<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-pu6wzxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i-pu6wzxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:home-fill-16" /></template>
