<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zgcba5bww.css';
import '../../css/n/nk1speb3h.css';
import '../../css/f/ffrnjebod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zgcba5bww"/><path class="nk1speb3h"/><path class="ffrnjebod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:dictionary-language-book-flat" /></template>
