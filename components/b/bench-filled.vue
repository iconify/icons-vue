<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg0lz9bfx.css';
import '../../css/y/y-np30t2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="lg0lz9bfx"/><path class="y-np30t2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bench-filled" /></template>
