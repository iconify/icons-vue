<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/f/f3xl7f2bt.css';
import '../../css/a/a2jwblbfm.css';
import '../../css/j/joeryvb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="f3xl7f2bt"/><path class="a2jwblbfm"/><path class="joeryvb2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cloud-error-light" /></template>
