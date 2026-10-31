<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-d7dab2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-d7dab2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-o-duotone-round" /></template>
