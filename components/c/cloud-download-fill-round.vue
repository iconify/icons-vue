<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clu1kebvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clu1kebvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-download-fill-round" /></template>
