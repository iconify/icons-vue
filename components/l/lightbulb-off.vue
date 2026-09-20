<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uffskhb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uffskhb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:lightbulb-off" /></template>
