<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4kv38r6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4kv38r6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:a-b" /></template>
