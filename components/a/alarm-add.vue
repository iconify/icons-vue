<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5wi-ryfk.css';
import '../../css/n/nwfb1ibqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5wi-ryfk"/><path class="nwfb1ibqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:alarm-add" /></template>
