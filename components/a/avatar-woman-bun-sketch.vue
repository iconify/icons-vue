<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zhfr4tbaq.css';
import '../../css/e/eo_o8eb7r.css';
import '../../css/t/tqwue9bav.css';
import '../../css/g/g-wgd2bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zhfr4tbaq"/><path class="eo_o8eb7r wm-k"/><path class="tqwue9bav wm-a"/><path class="g-wgd2bcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-woman-bun-sketch" /></template>
