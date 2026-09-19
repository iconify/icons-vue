<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg-wgrjyj.css';
import '../../css/l/lmzdaxwoj.css';
import '../../css/n/nd2aiyu9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="yg-wgrjyj"><path class="lmzdaxwoj"/><path class="nd2aiyu9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:gas-tank-droplet" /></template>
