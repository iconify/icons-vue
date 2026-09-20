<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjg98wbmn.css';
import '../../css/m/m889_pbai.css';
import '../../css/u/uh4pez9bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sjg98wbmn"/><path class="m889_pbai"/><path class="uh4pez9bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-flip-vertical-up" /></template>
