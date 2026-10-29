<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/vu12olbyp.css';
import '../../css/x/x56nlvbqu.css';
import '../../css/z/zgi57wboo.css';
import '../../css/c/cn7mk_15d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="vu12olbyp wm-deco"/><path class="wm-deco x56nlvbqu"/><path class="wm-deco zgi57wboo"/><path class="cn7mk_15d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:candy-blueprint" /></template>
