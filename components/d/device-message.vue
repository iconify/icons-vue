<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/cxmgx1b1q.css';
import '../../css/u/uhmn79b9g.css';
import '../../css/t/t7ohwjbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cxmgx1b1q"/><path class="uhmn79b9g"/><path class="t7ohwjbde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:device-message" /></template>
