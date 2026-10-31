<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phgq0i6ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phgq0i6ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-help-fill-round" /></template>
