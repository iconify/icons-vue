<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8jg2bc8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8jg2bc8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-dollar-duotone-round" /></template>
