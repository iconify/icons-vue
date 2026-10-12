<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh5rds2bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fh5rds2bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fan-filled" /></template>
