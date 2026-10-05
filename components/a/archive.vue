<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/f/fwt4_36rp.css';
import '../../css/f/fqa1e_awf.css';
import '../../css/y/ykall_bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="fwt4_36rp"/><path class="fqa1e_awf"/><path class="ykall_bto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:archive" /></template>
