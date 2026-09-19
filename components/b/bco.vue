<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jg3relvbv.css';
import '../../css/i/iu6iqfljn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="jg3relvbv"/><path class="iu6iqfljn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:bco" /></template>
