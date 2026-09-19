<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs6tz1b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fs6tz1b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:arrow-left2" /></template>
