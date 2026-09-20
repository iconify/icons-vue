<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udxfvrbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="udxfvrbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:density-m-outline" /></template>
