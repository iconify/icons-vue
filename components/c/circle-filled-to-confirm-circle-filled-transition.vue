<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8wpfy.css';
import '../../css/t/t5pxry.css';
import '../../css/o/ovwh-q.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-14.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGlrN5objY"><path class="p8wpfy t5pxry"/><path class="ovwh-q t5pxry"/></mask></defs><path mask="url(#SVGlrN5objY)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:circle-filled-to-confirm-circle-filled-transition" /></template>
