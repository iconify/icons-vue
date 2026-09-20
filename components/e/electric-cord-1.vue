<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xck5rbc3z.css';
import '../../css/c/ceu6ypbbo.css';
import '../../css/c/cor_1wsgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="xck5rbc3z"><path class="ceu6ypbbo"/><path class="cor_1wsgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:electric-cord-1" /></template>
