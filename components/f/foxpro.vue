<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2dw42tyk.css';
import '../../css/n/n9q2ej5ie.css';
import '../../css/m/mnz3z3wzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="c2dw42tyk"/><path class="n9q2ej5ie"/><path class="mnz3z3wzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:foxpro" /></template>
