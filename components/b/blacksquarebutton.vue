<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjqaj78ut.css';
import '../../css/z/zra9s3b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rjqaj78ut"/><path class="zra9s3b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:blacksquarebutton" /></template>
