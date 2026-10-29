<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nf1sxrb8v.css';
import '../../css/f/fmyq8ctie.css';
import '../../css/z/zi3qf8bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nf1sxrb8v"/><path class="fmyq8ctie wm-k"/><path class="wm-a zi3qf8bqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:candy-cane-sketch" /></template>
