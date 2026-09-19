<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jz1mobb4k.css';
import '../../css/t/tnsmnzdvo.css';
import '../../css/e/ecyiiytap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><circle class="jz1mobb4k"/><circle class="tnsmnzdvo"/><circle class="ecyiiytap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:ellipsis-26" /></template>
