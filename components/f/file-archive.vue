<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf58epbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf58epbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-archive" /></template>
