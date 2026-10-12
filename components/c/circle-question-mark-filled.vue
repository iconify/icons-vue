<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oal6mpb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oal6mpb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-question-mark-filled" /></template>
