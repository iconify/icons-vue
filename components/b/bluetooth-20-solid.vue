<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfuv_1wwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mfuv_1wwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bluetooth-20-solid" /></template>
