<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1d4pkb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="i1d4pkb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:generic-scan-filled" /></template>
