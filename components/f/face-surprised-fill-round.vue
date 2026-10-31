<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh8trchkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh8trchkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-surprised-fill-round" /></template>
