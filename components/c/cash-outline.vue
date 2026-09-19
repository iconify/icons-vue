<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmr_-4ywv.css';
import '../../css/p/p2tzfnyio.css';
import '../../css/h/hb0uf1bvc.css';
import '../../css/i/i-p-10b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect transform="matrix(-1 0 0 -1 512 416)" class="wmr_-4ywv"/><path class="p2tzfnyio"/><circle class="hb0uf1bvc"/><path class="i-p-10b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cash-outline" /></template>
