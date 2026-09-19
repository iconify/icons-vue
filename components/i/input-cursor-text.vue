<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1y6vhbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1y6vhbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:input-cursor-text" /></template>
