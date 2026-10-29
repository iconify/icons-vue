<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8zpfcn6o.css';
import '../../css/u/umo6mlbcr.css';
import '../../css/n/n_y009b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8zpfcn6o"/><path class="umo6mlbcr"/><path class="n_y009b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:files" /></template>
