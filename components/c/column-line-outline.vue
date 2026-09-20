<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us_qw2b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="us_qw2b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:column-line-outline" /></template>
