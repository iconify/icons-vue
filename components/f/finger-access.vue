<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/czd7etboj.css';
import '../../css/i/ihar8za-j.css';
import '../../css/d/dq9es6cpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="czd7etboj"/><path class="ihar8za-j"/><path class="dq9es6cpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:finger-access" /></template>
