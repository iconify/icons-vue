<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9veuqatq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9veuqatq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:brain-ai-3-fill" /></template>
