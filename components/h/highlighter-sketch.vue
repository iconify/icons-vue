<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/ox-omcb5y.css';
import '../../css/e/e1d1vryur.css';
import '../../css/x/xq-_h1b-e.css';
import '../../css/z/zma78gb_v.css';
import '../../css/q/q86-s3brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ox-omcb5y"/><path class="e1d1vryur wm-k"/><path class="wm-a xq-_h1b-e"/><path class="wm-k zma78gb_v"/><path class="q86-s3brj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:highlighter-sketch" /></template>
