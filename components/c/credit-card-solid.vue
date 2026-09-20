<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxlczvqqd.css';
import '../../css/m/m8_h6-bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pxlczvqqd"/><path clip-rule="evenodd" class="m8_h6-bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:credit-card-solid" /></template>
