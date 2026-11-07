<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo0l9j9lh.css';
import '../../css/n/nk-dx3faz.css';
import '../../css/q/ql2i1fbyo.css';
import '../../css/e/eusfa-1-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo0l9j9lh"/><path clip-rule="evenodd" class="nk-dx3faz"/><path class="ql2i1fbyo"/><path class="eusfa-1-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layers-bold" /></template>
