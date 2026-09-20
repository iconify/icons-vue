<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p79z853-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p79z853-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hierarchy-8-remix" /></template>
