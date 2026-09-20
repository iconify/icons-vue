<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um3320xwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="um3320xwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:distribution-outline" /></template>
