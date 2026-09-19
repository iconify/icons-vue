<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gtycj1ond.css';
import '../../css/h/h_5f6couv.css';
import '../../css/l/ludnwn2qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="gtycj1ond"/><path clip-rule="evenodd" class="h_5f6couv"/><path clip-rule="evenodd" class="ludnwn2qt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:copilot-not-connected" /></template>
