<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsvdxy6pu.css';
import '../../css/i/i6axh2brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsvdxy6pu"/><path class="i6axh2brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-up-minimalistic-bold-duotone" /></template>
