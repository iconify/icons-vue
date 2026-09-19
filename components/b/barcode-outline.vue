<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm54_4bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lm54_4bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:barcode-outline" /></template>
