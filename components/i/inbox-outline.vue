<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy4rl4bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vy4rl4bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-outline" /></template>
