<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxhz2_bsp.css';
import '../../css/w/wbz7ex9hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxhz2_bsp"/><path class="wbz7ex9hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bsw" /></template>
