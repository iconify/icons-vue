<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0ikh52rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0ikh52rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:headphones" /></template>
