<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-a25uhrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-a25uhrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lift-in-window-open1" /></template>
