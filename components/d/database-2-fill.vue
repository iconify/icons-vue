<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-dgb1bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-dgb1bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:database-2-fill" /></template>
