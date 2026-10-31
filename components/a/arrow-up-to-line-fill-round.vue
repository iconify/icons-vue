<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnflv6btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnflv6btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-to-line-fill-round" /></template>
