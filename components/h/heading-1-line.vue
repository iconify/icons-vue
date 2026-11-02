<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej3erva_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej3erva_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heading-1-line" /></template>
