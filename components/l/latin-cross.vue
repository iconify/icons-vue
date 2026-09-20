<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo0zz1btx.css';
import '../../css/o/o7lpvfbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zo0zz1btx"/><path class="o7lpvfbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:latin-cross" /></template>
