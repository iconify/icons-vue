<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euy7x3bzx.css';
import '../../css/c/c7zalxt4x.css';
import '../../css/l/la19u4bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="euy7x3bzx"/><path class="c7zalxt4x"/><path class="la19u4bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-unknown" /></template>
