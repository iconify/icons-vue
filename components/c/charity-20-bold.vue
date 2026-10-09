<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur5l4w8hg.css';
import '../../css/n/nqiq-nbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ur5l4w8hg"/><path class="nqiq-nbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charity-20-bold" /></template>
