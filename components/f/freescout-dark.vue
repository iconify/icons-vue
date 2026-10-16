<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha514kb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":96,"height":96};
const content = `<path class="ha514kb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:freescout-dark" /></template>
