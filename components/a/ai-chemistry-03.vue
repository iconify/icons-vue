<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljln6q8iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljln6q8iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-chemistry-03" /></template>
