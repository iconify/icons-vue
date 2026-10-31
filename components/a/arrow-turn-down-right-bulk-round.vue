<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrec87wmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrec87wmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-down-right-bulk-round" /></template>
