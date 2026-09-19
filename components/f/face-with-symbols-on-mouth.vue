<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rmf30cp6v.css';
import '../../css/f/f5tq5acha.css';
import '../../css/y/yq17t_xnl.css';
import '../../css/m/m_hfrwlhq.css';
import '../../css/w/wya1mhbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rmf30cp6v"/><path class="f5tq5acha"/><path class="yq17t_xnl"/><path class="m_hfrwlhq"/><path class="wya1mhbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:face-with-symbols-on-mouth" /></template>
