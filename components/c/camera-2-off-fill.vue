<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt1553bbb.css';
import '../../css/i/iua5r4byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mt1553bbb"/><path class="iua5r4byv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-2-off-fill" /></template>
