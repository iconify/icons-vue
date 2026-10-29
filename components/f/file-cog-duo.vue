<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/h39yknwhx.css';
import '../../css/z/z2owcnb2l.css';
import '../../css/q/q8vdfbk1f.css';
import '../../css/j/j6807mbiw.css';
import '../../css/z/z4bbp2bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="h39yknwhx"/><path class="wm-s z2owcnb2l"/><path class="q8vdfbk1f wm-s"/><path class="j6807mbiw"/><path class="wm-a z4bbp2bhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-cog-duo" /></template>
