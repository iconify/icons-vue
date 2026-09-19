<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/a8yocrbjl.css';
import '../../css/q/qbxa08-op.css';
import '../../css/d/dwzk6j57p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><ellipse transform="rotate(45)" class="a8yocrbjl"/><ellipse transform="rotate(315)" class="qbxa08-op"/><path class="dwzk6j57p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:atom" /></template>
