<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc8meib2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc8meib2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:chat-bubble-warning" /></template>
