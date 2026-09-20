<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jysc-acmf.css';
import '../../css/f/flr8mw1dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jysc-acmf"/><path class="flr8mw1dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:html3" /></template>
