<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8t7dyboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8t7dyboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-2-line" /></template>
