<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu25cdcsl.css';
import '../../css/a/af8m14f_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mu25cdcsl"/><path clip-rule="evenodd" class="af8m14f_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:certificate-16" /></template>
