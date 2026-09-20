<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyw1nmuwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyw1nmuwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-bebo" /></template>
