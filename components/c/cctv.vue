<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8__b9zxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8__b9zxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cctv" /></template>
