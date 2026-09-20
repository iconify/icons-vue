<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u16dxc66j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u16dxc66j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:claris-logo-solid" /></template>
