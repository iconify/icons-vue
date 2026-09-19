<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa24fvbdv.css';
import '../../css/f/fd7vi_cbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xa24fvbdv"/><path class="fd7vi_cbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-browsers-outline" /></template>
