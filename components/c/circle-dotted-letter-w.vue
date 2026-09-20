<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgcm3wb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgcm3wb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dotted-letter-w" /></template>
