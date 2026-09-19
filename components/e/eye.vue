<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/aprbvlbti.css';
import '../../css/o/oclsbd5zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="aprbvlbti"/><circle class="oclsbd5zw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:eye" /></template>
