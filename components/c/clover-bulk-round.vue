<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuvy8ubpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuvy8ubpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clover-bulk-round" /></template>
