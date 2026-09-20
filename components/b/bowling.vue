<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6l_-lb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x6l_-lb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bowling" /></template>
