<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q26luwbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q26luwbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-more-horizontal-fill-round" /></template>
