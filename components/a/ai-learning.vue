<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_9q84bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_9q84bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-learning" /></template>
