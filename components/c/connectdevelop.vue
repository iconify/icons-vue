<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eppxe-npy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eppxe-npy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:connectdevelop" /></template>
