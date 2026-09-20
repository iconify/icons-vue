<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hs0n-qjnn.css';
import '../../css/c/cuekppbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hs0n-qjnn"/><path class="cuekppbqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:landscape-lock-flat" /></template>
