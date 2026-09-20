<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsn7_zb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rsn7_zb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:center-horizontally-outline" /></template>
