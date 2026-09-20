<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8_wgcx8k.css';
import '../../css/t/t1ypfb_hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i8_wgcx8k"/><path class="t1ypfb_hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aviato" /></template>
