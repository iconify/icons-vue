<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vdzw6oeal.css';
import '../../css/f/fm3s1pbab.css';
import '../../css/q/qdabs8b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="vdzw6oeal"/><path class="fm3s1pbab"/><path clip-rule="evenodd" class="qdabs8b6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:earbuds-left-filled" /></template>
