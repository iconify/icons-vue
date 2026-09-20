<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aruy6vbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aruy6vbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ctg" /></template>
