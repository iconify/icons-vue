<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipsnr06wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ipsnr06wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-mail" /></template>
