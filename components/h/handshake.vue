<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/c/c2-vhivfe.css';
import '../../css/c/c9ar02bkm.css';
import '../../css/g/gxrw9vbxr.css';
import '../../css/f/f4or7pb1c.css';
import '../../css/r/rh9qoibkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="c2-vhivfe"/><path class="c9ar02bkm wm-shine"/><path class="gxrw9vbxr wm-k"/><path class="f4or7pb1c wm-a"/><path class="rh9qoibkn wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:handshake" /></template>
