<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fz5mlfa2u.css';
import '../../css/j/jdbl7utrz.css';
import '../../css/e/e25jo1u6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fz5mlfa2u"/><path class="jdbl7utrz"/><path class="e25jo1u6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:drone-flat" /></template>
