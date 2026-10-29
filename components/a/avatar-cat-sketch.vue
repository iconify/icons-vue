<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e57mt9qpn.css';
import '../../css/f/fzq5egeqa.css';
import '../../css/b/bi9r08orm.css';
import '../../css/w/wopk95bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e57mt9qpn"/><path class="fzq5egeqa wm-a"/><path class="bi9r08orm wm-k"/><path class="wm-a wopk95bgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-cat-sketch" /></template>
