<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/r/ryfxsnb7k.css';
import '../../css/t/t3g9whbyu.css';
import '../../css/f/fdp_8i46o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="ryfxsnb7k"/><path class="t3g9whbyu"/><path class="fdp_8i46o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:bell" /></template>
