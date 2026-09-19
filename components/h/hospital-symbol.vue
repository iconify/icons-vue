<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n58zy-blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n58zy-blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hospital-symbol" /></template>
