<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fc3kbgmfl.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/a/ahz5bx2fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fc3kbgmfl"/><path class="qr4ochb5c wm-s"/><path class="ahz5bx2fp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bluetooth-off-duo" /></template>
