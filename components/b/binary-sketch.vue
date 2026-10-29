<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f3ro08kee.css';
import '../../css/n/n4g9u7rzq.css';
import '../../css/g/g0y139bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f3ro08kee wm-a"/><path class="n4g9u7rzq wm-k"/><path class="g0y139bsq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:binary-sketch" /></template>
