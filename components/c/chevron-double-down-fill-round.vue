<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6wfp6b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6wfp6b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-double-down-fill-round" /></template>
