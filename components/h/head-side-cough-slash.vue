<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np_7-4bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="np_7-4bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:head-side-cough-slash" /></template>
