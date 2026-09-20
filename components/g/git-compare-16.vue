<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha_v22dby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ha_v22dby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-compare-16" /></template>
