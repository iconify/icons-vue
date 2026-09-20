<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mzi5jpiyt.css';
import '../../css/q/qirpgzb7b.css';
import '../../css/p/p5hg2wbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mzi5jpiyt"/><path class="qirpgzb7b"/><path class="p5hg2wbjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:coupon" /></template>
