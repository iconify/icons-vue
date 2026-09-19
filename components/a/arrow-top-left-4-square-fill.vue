<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn95y1o2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jn95y1o2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-left-4-square-fill" /></template>
