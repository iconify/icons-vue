<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_8v8gnuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h_8v8gnuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:facebook" /></template>
