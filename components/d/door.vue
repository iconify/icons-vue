<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/kinyqzbsz.css';
import '../../css/s/szjd6r78e.css';
import '../../css/p/p103cbcyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(4 3)" class="bi12bsetm"><path class="kinyqzbsz"/><path class="szjd6r78e"/><circle class="p103cbcyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:door" /></template>
