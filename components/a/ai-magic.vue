<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-lijpi7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-lijpi7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-magic" /></template>
