<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m7of0hbqk.css';
import '../../css/k/klhdv0ueo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(2 3)" class="bi12bsetm"><path class="m7of0hbqk"/><circle class="klhdv0ueo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:gauge" /></template>
