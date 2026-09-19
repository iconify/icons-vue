<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsmu98p6c.css';
import '../../css/h/hs-tb-btz.css';
import '../../css/m/mc75m8d8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="xsmu98p6c"/><path class="hs-tb-btz"/><path class="mc75m8d8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:envelope" /></template>
