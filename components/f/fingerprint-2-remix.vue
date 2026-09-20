<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am3ffrobd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="am3ffrobd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:fingerprint-2-remix" /></template>
