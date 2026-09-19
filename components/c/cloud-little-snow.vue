<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i52jnbbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i52jnbbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-little-snow" /></template>
