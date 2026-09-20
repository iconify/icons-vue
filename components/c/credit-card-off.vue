<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h1k6ax5lh.css';
import '../../css/v/v65wkxheu.css';
import '../../css/h/h8pzlv1bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h1k6ax5lh"/><path clip-rule="evenodd" class="v65wkxheu"/><path class="h8pzlv1bf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:credit-card-off" /></template>
