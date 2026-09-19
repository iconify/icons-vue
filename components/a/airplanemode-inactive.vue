<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twmec-5-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":432};
const content = `<path class="twmec-5-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:airplanemode-inactive" /></template>
