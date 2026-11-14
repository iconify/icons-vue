<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/ko22q1b9a.css';
import '../../css/o/or9ywybpp.css';
import '../../css/h/hp_bkssfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ko22q1b9a"/><path class="or9ywybpp"/><path class="hp_bkssfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:idle-fee" /></template>
