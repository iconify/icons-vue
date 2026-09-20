<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro4-8abks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ro4-8abks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ice-cream-3-remix" /></template>
