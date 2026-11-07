<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu_991baa.css';
import '../../css/x/xrwz_e-ja.css';
import '../../css/z/z-vgfuljg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iu_991baa"/><path class="xrwz_e-ja"/><path class="z-vgfuljg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-sun-2-bold" /></template>
