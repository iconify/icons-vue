<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zi0-orbyi.css';
import '../../css/v/vblgq4bqe.css';
import '../../css/k/k20ru7b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zi0-orbyi"/><path class="vblgq4bqe"/><circle transform="matrix(-1 0 0 1 13 9.5)" class="k20ru7b2y"/><circle transform="matrix(-1 0 0 1 10 9.5)" class="k20ru7b2y"/><circle transform="matrix(-1 0 0 1 7 9.5)" class="k20ru7b2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:chats" /></template>
