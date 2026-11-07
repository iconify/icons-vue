<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpggx48vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpggx48vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-check-outline" /></template>
