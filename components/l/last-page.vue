<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je36gvb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je36gvb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:last-page" /></template>
