<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1biiwb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1biiwb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-down-small-fill-round" /></template>
