<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/b/blt9mhbec.css';
import '../../css/o/omoia8byb.css';
import '../../css/z/zgztdpbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="blt9mhbec"/><path class="omoia8byb"/><path class="zgztdpbiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:hash" /></template>
