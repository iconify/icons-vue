<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyx2zp.css';
import '../../css/t/t5pxry.css';
import '../../css/m/m5kcdn.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGc0U32cxc"><path class="pyx2zp t5pxry"/><path class="m5kcdn t5pxry"/></mask></defs><path mask="url(#SVGc0U32cxc)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:close-circle-filled" /></template>
