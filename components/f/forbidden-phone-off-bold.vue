<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kplff-6wx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kplff-6wx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:forbidden-phone-off-bold" /></template>
