<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkq91bbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkq91bbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-rotary-right" /></template>
