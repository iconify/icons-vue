<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vk3ftebjg.css';
import '../../css/i/iyp9w4pig.css';
import '../../css/p/p2im_9b3u.css';
import '../../css/i/ides4ac0q.css';
import '../../css/f/feucwswsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vk3ftebjg wm-k"/><path class="iyp9w4pig wm-a"/><path class="p2im_9b3u wm-shadow"/><path class="ides4ac0q wm-k"/><path class="feucwswsf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:eraser-engrave" /></template>
