<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqwl1ubue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqwl1ubue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:draw-ahead-filled" /></template>
