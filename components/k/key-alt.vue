<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s10zi1bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s10zi1bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:key-alt" /></template>
