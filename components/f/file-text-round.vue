<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj046jq3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aj046jq3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-text-round" /></template>
