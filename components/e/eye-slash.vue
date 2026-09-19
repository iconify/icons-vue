<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/q/qs5th2sbp.css';
import '../../css/j/j3zc7kn1m.css';
import '../../css/x/x3yzpi80d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="qs5th2sbp"/><path class="j3zc7kn1m"/><path class="x3yzpi80d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:eye-slash" /></template>
