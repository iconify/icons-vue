<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyex3lbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyex3lbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-x" /></template>
