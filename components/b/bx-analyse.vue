<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeo6el_jt.css';
import '../../css/o/op5c-pbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeo6el_jt"/><path class="op5c-pbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-analyse" /></template>
