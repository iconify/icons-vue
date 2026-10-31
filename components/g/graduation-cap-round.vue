<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6yzllbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6yzllbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:graduation-cap-round" /></template>
