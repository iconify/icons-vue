<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmzzx6u_m.css';
import '../../css/u/u-06obvoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xmzzx6u_m"/><path class="u-06obvoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flower-2-line" /></template>
