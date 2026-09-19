<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alnok1cnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="alnok1cnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-aligncenter" /></template>
