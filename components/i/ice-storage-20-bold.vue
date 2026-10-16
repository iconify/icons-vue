<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp_3l1bkn.css';
import '../../css/i/ij10vk6wc.css';
import '../../css/x/xa0ui5bez.css';
import '../../css/y/yw0epjfyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fp_3l1bkn"/><path class="ij10vk6wc"/><path class="xa0ui5bez"/><path class="yw0epjfyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ice-storage-20-bold" /></template>
