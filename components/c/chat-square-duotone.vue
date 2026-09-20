<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wgahfp6lw.css';
import '../../css/j/jnbwgabzh.css';
import '../../css/x/xyd6asbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wgahfp6lw"/><path clip-rule="evenodd" class="jnbwgabzh"/><path class="xyd6asbiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-square-duotone" /></template>
