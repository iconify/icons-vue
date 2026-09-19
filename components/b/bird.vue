<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haib0ymyx.css';
import '../../css/x/xvy96vm6v.css';
import '../../css/o/oj-zv3btu.css';
import '../../css/o/oas-wrbbc.css';
import '../../css/j/jcyri5utd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="haib0ymyx"/><path class="xvy96vm6v"/><path class="oj-zv3btu"/><path class="oas-wrbbc"/><path class="jcyri5utd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:bird" /></template>
