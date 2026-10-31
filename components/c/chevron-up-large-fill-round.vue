<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrqzfebyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrqzfebyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-up-large-fill-round" /></template>
