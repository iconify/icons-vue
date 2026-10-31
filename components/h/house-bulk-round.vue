<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp66z6jrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp66z6jrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-bulk-round" /></template>
