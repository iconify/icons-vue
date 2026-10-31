<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc9s3i56l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc9s3i56l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-bulk-round" /></template>
