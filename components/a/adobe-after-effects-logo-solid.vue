<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llgm2lbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="llgm2lbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:adobe-after-effects-logo-solid" /></template>
