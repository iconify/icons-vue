<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npvyk8bwj.css';
import '../../css/o/otc7hdckt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npvyk8bwj"/><path class="otc7hdckt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bluetooth" /></template>
