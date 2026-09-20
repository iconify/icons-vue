<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-f8xob-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h-f8xob-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lightbulb-bolt-bold" /></template>
