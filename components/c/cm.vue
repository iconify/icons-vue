<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jhjpckbvk.css';
import '../../css/e/ezvtrm6iz.css';
import '../../css/m/mg6lwxb5m.css';
import '../../css/q/qmdliab1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jhjpckbvk"/><path class="ezvtrm6iz"/><path class="mg6lwxb5m"/><path class="qmdliab1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:cm" /></template>
