<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p07bz681w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="p07bz681w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:book-reading" /></template>
