<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5humm8bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m5humm8bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lexware" /></template>
