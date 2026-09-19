<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiqe1-61x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":820};
const content = `<path class="wiqe1-61x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:comment" /></template>
