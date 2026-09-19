<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qdgw7wbwn.css';
import '../../css/c/ctew7ohvk.css';
import '../../css/j/jn_dmmhcx.css';
import '../../css/w/wtcy6bb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qdgw7wbwn"/><path class="ctew7ohvk"/><path class="jn_dmmhcx"/><path class="wtcy6bb6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:ma" /></template>
