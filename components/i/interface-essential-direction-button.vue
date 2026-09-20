<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz8e6mgxq.css';
import '../../css/v/vj-egbxkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iz8e6mgxq"/><path class="vj-egbxkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-direction-button" /></template>
