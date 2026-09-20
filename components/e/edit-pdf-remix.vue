<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eazp9w1_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eazp9w1_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:edit-pdf-remix" /></template>
