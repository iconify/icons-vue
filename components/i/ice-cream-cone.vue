<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_drazbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_drazbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:ice-cream-cone" /></template>
