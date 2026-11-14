<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/idhzit1_z.css';
import '../../css/z/zxw0ofxyz.css';
import '../../css/n/nt3ymrbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="idhzit1_z"/><path class="zxw0ofxyz"/><path class="nt3ymrbmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:analytics-up" /></template>
