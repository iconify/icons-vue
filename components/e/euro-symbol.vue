<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyc5tabsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyc5tabsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:euro-symbol" /></template>
