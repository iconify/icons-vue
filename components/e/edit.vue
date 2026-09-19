<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhwsd0bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":758,"height":666};
const content = `<path class="qhwsd0bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:edit" /></template>
