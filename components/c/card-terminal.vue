<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/z/zvfyfdbdi.css';
import '../../css/t/themptbtt.css';
import '../../css/u/uwm7z1qdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zvfyfdbdi"/><rect class="themptbtt"/><path class="uwm7z1qdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:card-terminal" /></template>
