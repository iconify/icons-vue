<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/m/m28cpcovm.css';
import '../../css/o/oceiybcet.css';
import '../../css/f/f8ufy2bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="m28cpcovm wm-k"/><path class="oceiybcet wm-a"/><path class="f8ufy2bhm wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:japanese-yen" /></template>
