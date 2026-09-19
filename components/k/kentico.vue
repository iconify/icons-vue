<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldv4xub-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ldv4xub-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:kentico" /></template>
