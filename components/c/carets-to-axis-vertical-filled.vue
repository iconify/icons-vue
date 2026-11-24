<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt_n8sqbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt_n8sqbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:carets-to-axis-vertical-filled" /></template>
