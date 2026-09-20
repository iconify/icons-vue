<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fb8vwhb_r.css';
import '../../css/u/ua-ambc_i.css';
import '../../css/w/wuvczemwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fb8vwhb_r"/><path class="ua-ambc_i"/><path clip-rule="evenodd" class="wuvczemwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:accessibility-outline" /></template>
