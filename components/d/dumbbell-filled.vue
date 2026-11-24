<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfr8ahb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfr8ahb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:dumbbell-filled" /></template>
