<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isf2-mbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isf2-mbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cell" /></template>
