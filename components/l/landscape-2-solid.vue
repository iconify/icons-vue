<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0x-y3z1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q0x-y3z1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:landscape-2-solid" /></template>
