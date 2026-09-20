<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz4b266xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz4b266xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-exclamation" /></template>
