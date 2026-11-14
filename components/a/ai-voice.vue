<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh0ml6b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh0ml6b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-voice" /></template>
