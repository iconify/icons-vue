<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msr53udzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="msr53udzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-iris-scan" /></template>
