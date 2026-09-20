<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr-1yfb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr-1yfb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bench" /></template>
