<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4t4-bchu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4t4-bchu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:circle-arrow-down" /></template>
