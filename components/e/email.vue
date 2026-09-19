<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msel8rbya.css';
import '../../css/z/zt3trxb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="msel8rbya"/><path class="zt3trxb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:email" /></template>
