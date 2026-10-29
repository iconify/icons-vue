<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzfv-sbvh.css';
import '../../css/f/fe3fg-bkg.css';
import '../../css/v/vs3nxnb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzfv-sbvh wm-shadow"/><path class="fe3fg-bkg wm-k"/><path class="vs3nxnb9l wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:arrow-right" /></template>
