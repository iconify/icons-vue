<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr_ojxbiy.css';
import '../../css/n/nr6iob5xa.css';
import '../../css/j/jv7dyx2xs.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/y/yyyukfddm.css';
import '../../css/k/kljvqjkjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tr_ojxbiy"/><path class="nr6iob5xa"/><path class="jv7dyx2xs"/><g class="brzn_0bpr"><path class="yyyukfddm"/><path class="kljvqjkjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:chair" /></template>
