<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1z4bsb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1z4bsb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:jcb-japan-credit-bureau-line" /></template>
