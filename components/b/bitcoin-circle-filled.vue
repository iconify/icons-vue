<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smd-g2-lg.css';
import '../../css/w/w9yumzbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smd-g2-lg"/><path clip-rule="evenodd" class="w9yumzbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:bitcoin-circle-filled" /></template>
