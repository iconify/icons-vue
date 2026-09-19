<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hl471tb-q.css';
import '../../css/h/hf3pd9fjs.css';
import '../../css/d/digy0rbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hl471tb-q"/><path class="hf3pd9fjs"/><path class="digy0rbjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:house-02" /></template>
