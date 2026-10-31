<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cset7o1an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cset7o1an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-left-small-duotone-round" /></template>
