<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6-qijb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6-qijb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:buy" /></template>
