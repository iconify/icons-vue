<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzwgsdbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzwgsdbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:magnet-01" /></template>
