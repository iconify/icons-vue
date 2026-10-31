<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n347d7blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n347d7blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-help-round" /></template>
