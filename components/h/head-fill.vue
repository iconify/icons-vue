<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz0debcgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz0debcgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:head-fill" /></template>
