<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky-a60blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ky-a60blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:glass" /></template>
