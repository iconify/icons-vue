<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgmhxkf8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zgmhxkf8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:doc-text" /></template>
