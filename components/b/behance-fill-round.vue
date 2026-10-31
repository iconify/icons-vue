<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/towhhu73f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="towhhu73f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:behance-fill-round" /></template>
