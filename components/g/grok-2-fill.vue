<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f05twi73b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f05twi73b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grok-2-fill" /></template>
