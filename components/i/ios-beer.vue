<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz6h4kbwi.css';
import '../../css/c/ctvx1x6ua.css';
import '../../css/q/qrplm35by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zz6h4kbwi"/><path class="ctvx1x6ua"/><path class="qrplm35by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-beer" /></template>
