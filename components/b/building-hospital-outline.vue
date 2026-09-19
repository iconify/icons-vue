<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m-pr96kgv.css';
import '../../css/k/kmjw4165b.css';
import '../../css/j/jtpo4t6rz.css';
import '../../css/e/eywdkpbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="m-pr96kgv"/><path class="kmjw4165b"/><path class="jtpo4t6rz"/><path class="eywdkpbyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:building-hospital-outline" /></template>
