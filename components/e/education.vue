<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mpr19ccyx.css';
import '../../css/o/ox2f6xb_t.css';
import '../../css/c/cjd1zynuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mpr19ccyx"/><path class="ox2f6xb_t"/><path class="cjd1zynuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:education" /></template>
