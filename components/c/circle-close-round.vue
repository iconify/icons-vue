<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8vpoib8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8vpoib8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-close-round" /></template>
