<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0f4p2b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0f4p2b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-right-small-bulk-round" /></template>
