<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7h-q9q4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7h-q9q4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anki-light" /></template>
