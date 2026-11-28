<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m97pjcb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m97pjcb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bell-check" /></template>
