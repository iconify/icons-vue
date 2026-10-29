<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n7orkhbbo.css';
import '../../css/j/j96vk5o1p.css';
import '../../css/q/qkgcggwyv.css';
import '../../css/u/u1qgtlh6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n7orkhbbo"/><path class="j96vk5o1p wm-a"/><path class="qkgcggwyv wm-k"/><path class="u1qgtlh6g wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bell-sketch" /></template>
