<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp_s0tzwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fp_s0tzwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cloud-off-solid" /></template>
