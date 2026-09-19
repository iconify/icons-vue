<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzt2ewbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzt2ewbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-add" /></template>
