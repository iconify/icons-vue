<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbmv7io-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbmv7io-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:close-outline" /></template>
