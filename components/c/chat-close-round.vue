<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6kv9-b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6kv9-b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-close-round" /></template>
