<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hesi3jb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hesi3jb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ladder-duo" /></template>
