<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imf12-b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="imf12-b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-grin-tongue-wink" /></template>
