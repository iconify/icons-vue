<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3k2hbbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3k2hbbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-circle-perspective-counterclockwise" /></template>
