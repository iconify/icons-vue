<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctw6q0b8o.css';
import '../../css/t/t9ct0qbqu.css';
import '../../css/z/zgqctgb3e.css';
import '../../css/z/z2vwp3pcc.css';
import '../../css/b/bdudq8bva.css';
import '../../css/n/nsr8pjb6l.css';
import '../../css/w/wdzq85bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctw6q0b8o wm-shadow"/><path class="t9ct0qbqu"/><path class="zgqctgb3e"/><path class="z2vwp3pcc"/><path class="bdudq8bva"/><path class="nsr8pjb6l wm-shine"/><path class="wdzq85bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-plush:audio-waveform" /></template>
