<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de_6mkbzh.css';
import '../../css/q/qgo6c_bos.css';
import '../../css/u/u3zbeznyl.css';
import '../../css/w/ww5vd8bvt.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 de_6mkbzh"/><path class="clr-i-outline clr-i-outline-path-2 qgo6c_bos"/><path class="clr-i-outline clr-i-outline-path-3 u3zbeznyl"/><path class="clr-i-outline clr-i-outline-path-4 ww5vd8bvt"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:add-text-line" /></template>
