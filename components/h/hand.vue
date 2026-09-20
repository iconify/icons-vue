<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/v6f07cc4u.css';
import '../../css/f/fj-ipp45f.css';
import '../../css/g/gqos64b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v6f07cc4u"/><path class="fj-ipp45f"/><path class="gqos64b9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:hand" /></template>
