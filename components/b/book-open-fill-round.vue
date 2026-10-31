<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lenp-1-db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lenp-1-db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-open-fill-round" /></template>
