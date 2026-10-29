<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jtvgcub6s.css';
import '../../css/k/ko90xuffb.css';
import '../../css/c/c52kkio2j.css';
import '../../css/i/i5siowb7c.css';
import '../../css/n/nq1o8dbmy.css';
import '../../css/z/zmtzvh1db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jtvgcub6s wm-k"/><path class="ko90xuffb wm-k"/><path class="c52kkio2j wm-k"/><path class="i5siowb7c wm-a"/><path class="nq1o8dbmy wm-k"/><path class="wm-k zmtzvh1db"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-girl-sketch" /></template>
