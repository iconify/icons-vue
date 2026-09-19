<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8rtl1bmh.css';
import '../../css/k/kcrnsgfwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8rtl1bmh"/><path class="kcrnsgfwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:cloud-upload" /></template>
