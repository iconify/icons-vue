<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-z7kfb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-z7kfb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-left-fill-round" /></template>
