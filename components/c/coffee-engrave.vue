<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zuwpiec5r.css';
import '../../css/a/a5vht7b5e.css';
import '../../css/l/l1trulqsp.css';
import '../../css/o/o7ull5bnt.css';
import '../../css/g/g9g2iobxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k zuwpiec5r"/><path class="a5vht7b5e wm-a"/><path class="l1trulqsp wm-shadow"/><path class="o7ull5bnt wm-k"/><path class="g9g2iobxb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:coffee-engrave" /></template>
