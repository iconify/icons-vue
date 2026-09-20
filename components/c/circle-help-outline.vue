<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps9e_1buy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ps9e_1buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:circle-help-outline" /></template>
