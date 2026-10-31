<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9w7y1w0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9w7y1w0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-bulk-round" /></template>
