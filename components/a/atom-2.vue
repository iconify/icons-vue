<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9buy9til.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9buy9til"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:atom-2" /></template>
