<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhz0dobwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhz0dobwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chevron-down-left" /></template>
