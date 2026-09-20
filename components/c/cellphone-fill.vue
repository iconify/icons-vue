<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxh3p_uns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dxh3p_uns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cellphone-fill" /></template>
