<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg-suhcje.css';
import '../../css/c/c8rfqr2hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg-suhcje"/><path class="c8rfqr2hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-2-line" /></template>
