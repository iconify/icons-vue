<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl90geboo.css';
import '../../css/h/h695rk-bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl90geboo"/><path class="h695rk-bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-cny-fill" /></template>
