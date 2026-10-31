<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpguz0bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpguz0bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-sparkle-round" /></template>
