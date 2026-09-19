<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w3ezo_bpd.css';
import '../../css/q/qs7d5jb9u.css';
import '../../css/m/mn_9mqnpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w3ezo_bpd"/><path class="qs7d5jb9u"/><path class="mn_9mqnpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:clipboard-document-solid" /></template>
