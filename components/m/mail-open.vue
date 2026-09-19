<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztxo5g_wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ztxo5g_wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:mail-open" /></template>
