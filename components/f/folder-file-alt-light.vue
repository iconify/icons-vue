<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/x/xrfgp0bpp.css';
import '../../css/v/vc02c23rw.css';
import '../../css/x/xtch0nbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="xrfgp0bpp"/><path class="vc02c23rw"/><path class="xtch0nbcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-file-alt-light" /></template>
