<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhghdrbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhghdrbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-sync-fill" /></template>
