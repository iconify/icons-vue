<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmd3obcfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lmd3obcfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:calendar" /></template>
