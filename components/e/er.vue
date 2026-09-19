<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/msqbht_3s.css';
import '../../css/l/ly148kbmp.css';
import '../../css/z/z9ptkzzsm.css';
import '../../css/v/vihk52k_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="msqbht_3s"/><path class="ly148kbmp"/><path class="z9ptkzzsm"/><path class="vihk52k_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:er" /></template>
