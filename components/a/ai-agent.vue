<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x82-71d5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x82-71d5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ai-agent" /></template>
