<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/g/g1z4pnb_m.css';
import '../../css/l/lobj_3gyy.css';
import '../../css/a/ank-fxw4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="g1z4pnb_m"/><path class="lobj_3gyy"/><path class="ank-fxw4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:arrow-down-from-line" /></template>
