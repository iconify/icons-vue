<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sg4y2bccz.css';
import '../../css/y/yy3q-7_1g.css';
import '../../css/j/j5uo_2b9h.css';
import '../../css/c/c_w8saclo.css';
import '../../css/t/txj5lrrof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sg4y2bccz wm-k"/><path class="wm-a yy3q-7_1g"/><path class="j5uo_2b9h wm-shadow"/><path class="c_w8saclo wm-k"/><path class="txj5lrrof wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:layout-template-engrave" /></template>
