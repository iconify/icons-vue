<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/f-zk1w6vl.css';
import '../../css/j/jg6n16uty.css';
import '../../css/y/y5s1tcbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-zk1w6vl"/><path class="jg6n16uty"/><path class="y5s1tcbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:charging-time" /></template>
