<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7v__r5kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7v__r5kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-right-to-line-fill-round" /></template>
