<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s-6b-h1do.css';
import '../../css/h/h0mz56qad.css';
import '../../css/w/wtotfkwny.css';
import '../../css/b/bkqrqjg7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s-6b-h1do"/><path class="h0mz56qad"/><path class="wtotfkwny"/><path class="bkqrqjg7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:code-qr" /></template>
