<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0bwvu1em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0bwvu1em"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:emoji-line" /></template>
