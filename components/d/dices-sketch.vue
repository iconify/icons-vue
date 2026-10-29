<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cdz3knbtf.css';
import '../../css/j/ju1tlcb7y.css';
import '../../css/x/xjht12--e.css';
import '../../css/c/c_por8bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cdz3knbtf"/><path class="ju1tlcb7y wm-a"/><path class="wm-k xjht12--e"/><path class="c_por8bml wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dices-sketch" /></template>
