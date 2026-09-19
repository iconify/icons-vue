<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph19vw9nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ph19vw9nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:ligature" /></template>
