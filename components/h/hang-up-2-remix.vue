<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5ae8mb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o5ae8mb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hang-up-2-remix" /></template>
