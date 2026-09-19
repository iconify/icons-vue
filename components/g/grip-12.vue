<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bi10sjbpy.css';
import '../../css/m/mzq5g5bac.css';
import '../../css/e/ewwrtcb0r.css';
import '../../css/p/p5cjbq18d.css';
import '../../css/m/myv5azdfm.css';
import '../../css/h/hutszibpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><rect class="bi10sjbpy"/><rect class="mzq5g5bac"/><rect class="ewwrtcb0r"/><rect class="p5cjbq18d"/><rect class="myv5azdfm"/><rect class="hutszibpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:grip-12" /></template>
