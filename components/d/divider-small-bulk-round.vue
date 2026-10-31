<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er3-szkyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er3-szkyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:divider-small-bulk-round" /></template>
