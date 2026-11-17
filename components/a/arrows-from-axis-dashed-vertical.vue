<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c49mhrr1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c49mhrr1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrows-from-axis-dashed-vertical" /></template>
