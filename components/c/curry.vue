<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa52w5bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wa52w5bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:curry" /></template>
