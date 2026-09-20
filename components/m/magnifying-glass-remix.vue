<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am86nkbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="am86nkbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:magnifying-glass-remix" /></template>
