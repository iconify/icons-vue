<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckj-49bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckj-49bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:code-simple" /></template>
