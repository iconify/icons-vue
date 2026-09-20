<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnr5p9b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":600,"height":600};
const content = `<path clip-rule="evenodd" class="qnr5p9b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codesandbox" /></template>
