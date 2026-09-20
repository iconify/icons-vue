<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2ft5u2rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2ft5u2rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-wifi-angle-bold" /></template>
