<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu6p-ybrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu6p-ybrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-diff-fill" /></template>
