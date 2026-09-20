<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fyirgbi5v.css';
import '../../css/z/zvlweubvr.css';
import '../../css/u/ubel4_bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fyirgbi5v"/><path class="zvlweubvr"/><path class="ubel4_bjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:gift-2-flat" /></template>
