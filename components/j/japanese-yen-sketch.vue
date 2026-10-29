<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f810mgb8e.css';
import '../../css/q/q_de4kb_g.css';
import '../../css/g/gwtyysm7e.css';
import '../../css/a/aahfikpfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f810mgb8e wm-k"/><path class="q_de4kb_g wm-a"/><path class="gwtyysm7e wm-k"/><path class="aahfikpfy wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:japanese-yen-sketch" /></template>
