<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zym4i3bis.css';
import '../../css/g/gafy37gmj.css';
import '../../css/i/ibt6e9bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="zym4i3bis"/><path class="gafy37gmj"/><path clip-rule="evenodd" class="ibt6e9bfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-send-bold" /></template>
