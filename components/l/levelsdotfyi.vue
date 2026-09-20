<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4zlabt2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4zlabt2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:levelsdotfyi" /></template>
