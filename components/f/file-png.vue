<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/raf6kmqmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="raf6kmqmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-png" /></template>
