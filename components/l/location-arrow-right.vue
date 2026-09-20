<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mik8_3b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="mik8_3b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:location-arrow-right" /></template>
