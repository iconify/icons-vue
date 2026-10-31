<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp1lhszbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp1lhszbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-right-large-duotone-round" /></template>
