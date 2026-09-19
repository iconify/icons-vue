<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvhcdebcd.css';
import '../../css/g/gsarlxfwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xvhcdebcd"/><path class="gsarlxfwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-download" /></template>
