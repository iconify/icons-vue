<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fzx9q9b-g.css';
import '../../css/a/aecemzbxq.css';
import '../../css/w/wu7pu2bgf.css';
import '../../css/z/z3lq_puen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fzx9q9b-g wm-k"/><path class="aecemzbxq wm-a"/><path class="wm-k wu7pu2bgf"/><path class="wm-a z3lq_puen"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-teen-sketch" /></template>
