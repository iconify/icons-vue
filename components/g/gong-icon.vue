<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr96rnsfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1900,"height":1900};
const content = `<path class="qr96rnsfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gong-icon" /></template>
