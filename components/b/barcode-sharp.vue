<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk0dibbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vk0dibbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:barcode-sharp" /></template>
