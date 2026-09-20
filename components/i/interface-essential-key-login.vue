<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6twclbpr.css';
import '../../css/p/poe7slbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u6twclbpr"/><path class="poe7slbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-key-login" /></template>
