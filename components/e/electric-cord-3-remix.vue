<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plls9j28h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plls9j28h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:electric-cord-3-remix" /></template>
