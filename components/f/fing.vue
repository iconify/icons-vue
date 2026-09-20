<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh8shv5-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh8shv5-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fing" /></template>
