<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3--6bbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j3--6bbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:delta-chat-dark" /></template>
