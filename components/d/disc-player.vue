<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4slxjbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4slxjbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:disc-player" /></template>
