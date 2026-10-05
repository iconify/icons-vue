<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/p/p83hcbb5i.css';
import '../../css/b/bdhwjlbuv.css';
import '../../css/c/cdux-b05b.css';
import '../../css/o/oemdzc2_z.css';
import '../../css/k/kvdr5wc5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="p83hcbb5i"/><path class="bdhwjlbuv"/><path class="cdux-b05b"/><path class="oemdzc2_z"/><path class="kvdr5wc5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:dimension" /></template>
