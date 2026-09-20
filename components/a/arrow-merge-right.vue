<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn9uko5kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn9uko5kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-merge-right" /></template>
