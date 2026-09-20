<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i36vu1bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i36vu1bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:line-height-2" /></template>
