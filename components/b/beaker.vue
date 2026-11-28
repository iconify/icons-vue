<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbp5w2bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbp5w2bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:beaker" /></template>
