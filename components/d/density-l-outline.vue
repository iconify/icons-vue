<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr7da0tze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jr7da0tze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:density-l-outline" /></template>
