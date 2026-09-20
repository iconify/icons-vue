<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fa2_mdbyf.css';
import '../../css/j/jcqo197tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(4 1)" class="bi12bsetm"><path class="fa2_mdbyf"/><circle class="jcqo197tm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:door-alt" /></template>
