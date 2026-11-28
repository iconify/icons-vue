<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6uzsk5wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f6uzsk5wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dispensing-machine" /></template>
