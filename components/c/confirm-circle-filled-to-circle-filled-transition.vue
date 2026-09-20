<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8wpfy.css';
import '../../css/t/t5pxry.css';
import '../../css/f/fb-lrs.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-to-14.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGmTAR7Qud"><path class="p8wpfy t5pxry"/><path class="fb-lrs t5pxry"/></mask></defs><path mask="url(#SVGmTAR7Qud)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:confirm-circle-filled-to-circle-filled-transition" /></template>
