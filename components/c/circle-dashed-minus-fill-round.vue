<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch-5vob4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch-5vob4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-minus-fill-round" /></template>
