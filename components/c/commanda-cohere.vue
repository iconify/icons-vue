<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmwnk3p6s.css';
import '../../css/u/uar01lb2v.css';
import '../../css/p/p2sew--qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmwnk3p6s"/><path clip-rule="evenodd" class="uar01lb2v"/><path class="p2sew--qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:commanda-cohere" /></template>
