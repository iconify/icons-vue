<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/h754ff_bs.css';
import '../../css/t/tjznz3bqe.css';
import '../../css/u/uzt_qbcfs.css';
import '../../css/v/vfrwuab3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="h754ff_bs"/><path class="tjznz3bqe"/><path class="uzt_qbcfs"/><path class="vfrwuab3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:building-2-outline" /></template>
