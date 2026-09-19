<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qili0cbnj.css';
import '../../css/i/iq65ps9zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qili0cbnj"/><path class="iq65ps9zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-export" /></template>
