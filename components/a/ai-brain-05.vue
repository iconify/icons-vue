<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj07quejt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj07quejt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-brain-05" /></template>
