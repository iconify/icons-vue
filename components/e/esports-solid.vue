<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyi4y7bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oyi4y7bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:esports-solid" /></template>
