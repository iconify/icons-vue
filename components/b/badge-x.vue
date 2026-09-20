<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udt21abpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udt21abpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge-x" /></template>
