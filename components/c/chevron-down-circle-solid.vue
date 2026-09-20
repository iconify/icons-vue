<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmbq64bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmbq64bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-down-circle-solid" /></template>
