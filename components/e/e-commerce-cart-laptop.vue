<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/oqg364tlq.css';
import '../../css/q/qq-clrhce.css';
import '../../css/r/r68pqmbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="oqg364tlq"/><path class="qq-clrhce"/><path class="r68pqmbnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:e-commerce-cart-laptop" /></template>
