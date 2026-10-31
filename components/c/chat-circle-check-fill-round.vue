<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhpqz8y6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhpqz8y6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-check-fill-round" /></template>
