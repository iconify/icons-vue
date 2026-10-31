<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4fgcfq9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4fgcfq9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-4-fill-round" /></template>
