<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/ek_0oyb1o.css';
import '../../css/j/jxyaplgzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(5 3)" class="bi12bsetm"><path class="ek_0oyb1o"/><circle class="jxyaplgzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:iphone-portrait" /></template>
