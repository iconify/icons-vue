<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doqujn1zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="doqujn1zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:investing-and-banking-remix" /></template>
