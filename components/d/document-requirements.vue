<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dybeleg8o.css';
import '../../css/l/lxih1s-hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dybeleg8o"/><path class="lxih1s-hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-requirements" /></template>
