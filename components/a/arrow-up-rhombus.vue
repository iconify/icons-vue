<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db6myboly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db6myboly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-up-rhombus" /></template>
