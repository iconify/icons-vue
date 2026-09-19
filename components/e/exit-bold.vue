<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orni8mdcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orni8mdcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:exit-bold" /></template>
