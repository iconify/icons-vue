<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1un71jxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i1un71jxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:building-outline" /></template>
