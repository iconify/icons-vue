<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq0yy1vxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vq0yy1vxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:leetcode" /></template>
