<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrd_d7bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vrd_d7bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:linux-mint-logo-2-block" /></template>
