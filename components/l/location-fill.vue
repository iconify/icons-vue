<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyss1-bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyss1-bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:location-fill" /></template>
