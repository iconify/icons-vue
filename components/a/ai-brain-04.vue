<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g93ksbc7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g93ksbc7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-brain-04" /></template>
