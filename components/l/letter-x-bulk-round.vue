<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umpfuubtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umpfuubtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-x-bulk-round" /></template>
