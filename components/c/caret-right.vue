<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw7k_9bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw7k_9bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:caret-right" /></template>
