<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v12d60_ju.css';
import '../../css/e/e29tvgbxj.css';
import '../../css/q/qdaqy6blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v12d60_ju"/><path class="e29tvgbxj"/><path class="qdaqy6blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coolify" /></template>
