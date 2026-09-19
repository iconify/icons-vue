<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upjig_pzx.css';
import '../../css/m/mii1e_b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upjig_pzx"/><path clip-rule="evenodd" class="mii1e_b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:iou-filled" /></template>
