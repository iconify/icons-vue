<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3es_9_li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3es_9_li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:layers-2" /></template>
