<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz1ow95wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz1ow95wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-badge-dollar" /></template>
