<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1z4rnb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1z4rnb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eyebrow-fill" /></template>
