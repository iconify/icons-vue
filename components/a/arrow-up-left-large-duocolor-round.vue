<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1n2jnbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1n2jnbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-left-large-duocolor-round" /></template>
