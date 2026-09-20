<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm84comle.css';
import '../../css/l/l2q_0xbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pm84comle"/><path class="l2q_0xbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-acrobat" /></template>
