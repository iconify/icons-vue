<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb31-2bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sb31-2bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:emoji-neutral" /></template>
