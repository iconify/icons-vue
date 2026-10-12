<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isxvafbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="isxvafbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clock-7-filled" /></template>
