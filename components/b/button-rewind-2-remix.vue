<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2w1l-2qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r2w1l-2qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-rewind-2-remix" /></template>
