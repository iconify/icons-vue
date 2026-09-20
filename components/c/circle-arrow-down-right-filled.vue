<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buk670bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buk670bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-arrow-down-right-filled" /></template>
