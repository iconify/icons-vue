<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kr89-5bas.css';
import '../../css/e/epj0hxbqe.css';
import '../../css/w/w88g0g3vx.css';
import '../../css/i/i_kfu3tmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kr89-5bas"/><path class="epj0hxbqe wm-a"/><path class="w88g0g3vx wm-k"/><path class="i_kfu3tmd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:candy-bucket-sketch" /></template>
