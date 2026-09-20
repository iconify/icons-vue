<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-6x6o-1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v-6x6o-1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:electric-cord-1-remix" /></template>
