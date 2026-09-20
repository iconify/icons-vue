<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meu77l_qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="meu77l_qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:cnn-logo-block" /></template>
