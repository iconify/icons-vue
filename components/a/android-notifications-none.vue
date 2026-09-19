<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6tlb2bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t6tlb2bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-notifications-none" /></template>
