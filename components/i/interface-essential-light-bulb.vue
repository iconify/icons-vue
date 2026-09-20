<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktz2u4-vt.css';
import '../../css/y/y72en9ydc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ktz2u4-vt"/><path class="y72en9ydc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-light-bulb" /></template>
