<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/ok6k5b6nb.css';
import '../../css/e/emdkxcbdp.css';
import '../../css/o/owc868bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ok6k5b6nb"/><path class="emdkxcbdp"/><path class="owc868bvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:covid-19-virus-pandemic-1" /></template>
