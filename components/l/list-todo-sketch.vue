<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/s5lv8gbfq.css';
import '../../css/g/g2knpnl4g.css';
import '../../css/e/ecoxr8ars.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="s5lv8gbfq wm-k"/><path class="g2knpnl4g wm-a"/><path class="ecoxr8ars wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-todo-sketch" /></template>
