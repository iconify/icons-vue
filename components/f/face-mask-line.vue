<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psi_79vqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psi_79vqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:face-mask-line" /></template>
