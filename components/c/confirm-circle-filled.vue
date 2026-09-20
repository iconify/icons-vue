<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyx2zp.css';
import '../../css/t/t5pxry.css';
import '../../css/u/u7rb2p.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGIeDYc1Gq"><path class="pyx2zp t5pxry"/><path class="t5pxry u7rb2p"/></mask></defs><path mask="url(#SVGIeDYc1Gq)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:confirm-circle-filled" /></template>
