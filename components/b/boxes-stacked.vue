<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbki43btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dbki43btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:boxes-stacked" /></template>
