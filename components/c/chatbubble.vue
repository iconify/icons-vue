<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df7gx9bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="df7gx9bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chatbubble" /></template>
