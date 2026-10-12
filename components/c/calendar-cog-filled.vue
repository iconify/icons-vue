<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-dh3gkit.css';
import '../../css/d/d8g489bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s-dh3gkit"/><path class="d8g489bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-cog-filled" /></template>
