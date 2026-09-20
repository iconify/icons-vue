<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/k6l9xwbnp.css';
import '../../css/c/cf8f9ynoi.css';
import '../../css/h/h1beiq6dv.css';
import '../../css/k/kxshi8bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="k6l9xwbnp"/><path class="cf8f9ynoi"/><path class="h1beiq6dv"/><path class="kxshi8bqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:loading-browser-bar" /></template>
