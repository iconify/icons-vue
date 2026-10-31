<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/m/mi9y5r1hc.css';
import '../../css/g/glvy3gwto.css';
import '../../css/w/whnw3ub8q.css';
import '../../css/b/b5i0fcb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="mi9y5r1hc wm-shadow"/><path class="glvy3gwto wm-shadow"/><path class="whnw3ub8q"/><path class="b5i0fcb6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:lollipop" /></template>
