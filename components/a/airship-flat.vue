<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/apz38mt4g.css';
import '../../css/h/ht5h3ou9h.css';
import '../../css/q/q26m725ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="apz38mt4g"/><path class="ht5h3ou9h"/><path class="q26m725ij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:airship-flat" /></template>
