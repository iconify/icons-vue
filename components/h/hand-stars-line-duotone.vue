<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/ch_n9zb8m.css';
import '../../css/o/og7lw7bbb.css';
import '../../css/b/b4_rsjb-p.css';
import '../../css/a/aw7yywbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ch_n9zb8m"/><path class="og7lw7bbb"/><path class="b4_rsjb-p"/><path class="aw7yywbhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hand-stars-line-duotone" /></template>
