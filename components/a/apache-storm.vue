<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk51emb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk51emb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:apache-storm" /></template>
