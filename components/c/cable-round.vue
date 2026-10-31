<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4v7tl5oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4v7tl5oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cable-round" /></template>
