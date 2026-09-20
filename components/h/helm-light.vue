<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyia3bbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iyia3bbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:helm-light" /></template>
