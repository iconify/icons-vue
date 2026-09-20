<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shwf02r4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="shwf02r4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:arrow-down-left-and-arrow-up-right-to-center" /></template>
