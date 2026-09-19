<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m8932utjo.css';
import '../../css/z/z7s7gzs3d.css';
import '../../css/j/jn6vfebhm.css';
import '../../css/r/ro21uzgez.css';
import '../../css/i/if22erdpj.css';
import '../../css/n/nng6jtbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="m8932utjo"/><path class="z7s7gzs3d"/><path class="jn6vfebhm"/><path class="ro21uzgez"/><path class="if22erdpj"/><path class="nng6jtbav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:cx" /></template>
