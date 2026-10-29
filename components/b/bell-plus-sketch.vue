<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eecxjrbnj.css';
import '../../css/p/p9r0hup0u.css';
import '../../css/w/wdmccygzx.css';
import '../../css/f/fhl8djbbm.css';
import '../../css/z/z77uqsqwc.css';
import '../../css/z/zqzdq927i.css';
import '../../css/m/mb79vbbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eecxjrbnj"/><path class="p9r0hup0u wm-k"/><path class="wdmccygzx wm-k"/><path class="fhl8djbbm wm-a"/><path class="wm-a z77uqsqwc"/><path class="wm-s zqzdq927i"/><path class="mb79vbbiy wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bell-plus-sketch" /></template>
