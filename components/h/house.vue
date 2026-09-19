<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/x/xq4i7fvzd.css';
import '../../css/c/c1f4szbmn.css';
import '../../css/r/ru21x0hju.css';
import '../../css/q/qmz1e48wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="xq4i7fvzd"/><path class="c1f4szbmn"/><path class="ru21x0hju"/><path class="qmz1e48wn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:house" /></template>
