<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmy-rlt6c.css';
import '../../css/l/l144cxb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xmy-rlt6c"/><path class="l144cxb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-game-controller-b" /></template>
