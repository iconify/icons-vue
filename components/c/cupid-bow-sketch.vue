<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sswb-xb6m.css';
import '../../css/x/xtwfm-rnu.css';
import '../../css/o/oj9xnhw5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sswb-xb6m wm-a"/><path class="wm-k xtwfm-rnu"/><path class="oj9xnhw5p wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cupid-bow-sketch" /></template>
