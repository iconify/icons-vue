<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/i/is8p2nbel.css';
import '../../css/r/r35bzkbxd.css';
import '../../css/w/wl97hswxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="is8p2nbel"/><path class="r35bzkbxd"/><path class="wl97hswxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:banana" /></template>
