<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bni1e42rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bni1e42rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ai-agents" /></template>
