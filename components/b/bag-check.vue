<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpxo15b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xpxo15b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bag-check" /></template>
