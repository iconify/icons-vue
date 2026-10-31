<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebt7lcckq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebt7lcckq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:info-bulk-round" /></template>
