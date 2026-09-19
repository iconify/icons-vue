<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvnybk8vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mvnybk8vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:copy" /></template>
