<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1a1f6wsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1a1f6wsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cat" /></template>
