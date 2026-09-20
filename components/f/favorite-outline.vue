<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmos9kbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmos9kbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:favorite-outline" /></template>
