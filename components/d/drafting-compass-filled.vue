<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlxa70wnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlxa70wnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:drafting-compass-filled" /></template>
