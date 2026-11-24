<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d43s5euap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d43s5euap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-question-mark-filled" /></template>
