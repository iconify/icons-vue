<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2yf3lfkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r2yf3lfkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gas-station-outline" /></template>
