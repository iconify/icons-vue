<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/aerk3sbog.css';
import '../../css/k/kjec_i-xm.css';
import '../../css/b/bkaybsb9q.css';
import '../../css/k/kx36_kbvm.css';
import '../../css/z/z-wr12dvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="aerk3sbog wm-k"/><path class="kjec_i-xm wm-k"/><path class="bkaybsb9q wm-k"/><path class="kx36_kbvm wm-k"/><path class="wm-k z-wr12dvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-person-sketch" /></template>
