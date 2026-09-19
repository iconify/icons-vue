<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftqjed4ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ftqjed4ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-bottom-center-16-solid" /></template>
