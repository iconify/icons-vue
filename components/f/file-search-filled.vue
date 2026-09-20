<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7kitb.css';
import '../../css/t/t5pxry.css';
import '../../css/q/q5vxhp.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-62.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGdXoEbuTb"><path class="j7kitb t5pxry"/><path class="q5vxhp t5pxry"/></mask></defs><path mask="url(#SVGdXoEbuTb)" class="botfzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:file-search-filled" /></template>
