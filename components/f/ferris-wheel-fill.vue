<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgz7q7b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgz7q7b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ferris-wheel-fill" /></template>
