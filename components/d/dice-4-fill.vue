<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixk8e1a3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixk8e1a3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dice-4-fill" /></template>
