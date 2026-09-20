<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifuufmagt.css';
import '../../css/u/ubv5z7b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="ifuufmagt"/><path class="ubv5z7b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:huff" /></template>
