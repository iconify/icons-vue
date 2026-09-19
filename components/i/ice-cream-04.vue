<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaz_ppzod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zaz_ppzod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ice-cream-04" /></template>
