<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/i/i6txspcqg.css';
import '../../css/z/zq5nnn5yu.css';
import '../../css/b/bewfq9f6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="i6txspcqg"/><path class="zq5nnn5yu"/><path class="bewfq9f6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:chess" /></template>
