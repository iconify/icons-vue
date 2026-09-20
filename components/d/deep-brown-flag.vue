<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlret9bua.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="xlret9bua"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:deep-brown-flag" /></template>
