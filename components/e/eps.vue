<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbt3_ecay.css';
import '../../css/a/awy61ibgu.css';
import '../../css/y/yln89_oby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":331.399};
const content = `<path clip-rule="evenodd" class="mbt3_ecay"/><path clip-rule="evenodd" class="awy61ibgu"/><path clip-rule="evenodd" class="yln89_oby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:eps" /></template>
