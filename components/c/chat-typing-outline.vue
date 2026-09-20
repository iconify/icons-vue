<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi-6e2h-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xi-6e2h-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:chat-typing-outline" /></template>
