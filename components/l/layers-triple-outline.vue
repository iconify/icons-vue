<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai7gqpb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai7gqpb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:layers-triple-outline" /></template>
