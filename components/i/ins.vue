<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zst3r7bmm.css';
import '../../css/l/l5yicfbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="zst3r7bmm"/><path class="l5yicfbnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ins" /></template>
