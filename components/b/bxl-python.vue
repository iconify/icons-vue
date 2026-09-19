<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcn2r4bsf.css';
import '../../css/k/kvlndpbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcn2r4bsf"/><path class="kvlndpbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-python" /></template>
