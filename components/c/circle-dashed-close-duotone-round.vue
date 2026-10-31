<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxw0ohbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxw0ohbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-close-duotone-round" /></template>
