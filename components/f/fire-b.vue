<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/blyr41bdj.css';
import '../../css/m/mv09pcb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="blyr41bdj"/><path class="mv09pcb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:fire-b" /></template>
