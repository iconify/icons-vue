<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u-b-jsbkc.css';
import '../../css/x/x796ssb0a.css';
import '../../css/p/ptmbtpbpn.css';
import '../../css/k/k1c77xo2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="u-b-jsbkc"/><path class="x796ssb0a"/><path clip-rule="evenodd" class="ptmbtpbpn"/><path clip-rule="evenodd" class="k1c77xo2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:flower" /></template>
