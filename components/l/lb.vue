<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/i-1p3lb_t.css';
import '../../css/k/kl8-xzbpl.css';
import '../../css/w/w6qdnyb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="i-1p3lb_t"/><path class="kl8-xzbpl"/><path class="w6qdnyb5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:lb" /></template>
