<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y15k2bb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y15k2bb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-upload-round" /></template>
