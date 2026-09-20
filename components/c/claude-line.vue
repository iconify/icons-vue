<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv40gtbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv40gtbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:claude-line" /></template>
