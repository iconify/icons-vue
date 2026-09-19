<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p22skhu_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p22skhu_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-right-1-light" /></template>
