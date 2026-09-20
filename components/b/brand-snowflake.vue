<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g69hyt1hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g69hyt1hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-snowflake" /></template>
