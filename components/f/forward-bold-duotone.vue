<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfs30bgfh.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/f/fh1mgzuzo.css';
import '../../css/s/s2p8flb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xfs30bgfh"/><g class="xtpeb-edw"><path class="fh1mgzuzo"/><path class="s2p8flb5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forward-bold-duotone" /></template>
