<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch1hirbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch1hirbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:barcode-outline" /></template>
