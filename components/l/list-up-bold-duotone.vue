<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtjo_wb4r.css';
import '../../css/i/i6axh2brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtjo_wb4r"/><path class="i6axh2brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-up-bold-duotone" /></template>
