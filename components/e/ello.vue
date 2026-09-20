<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al2951bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="al2951bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ello" /></template>
