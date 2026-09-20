<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9hl6jg0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9hl6jg0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cursor-speed-2" /></template>
