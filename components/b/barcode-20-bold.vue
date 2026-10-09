<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6eh32bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e6eh32bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:barcode-20-bold" /></template>
