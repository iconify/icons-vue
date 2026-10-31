<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig76nw-0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig76nw-0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:layer-round" /></template>
