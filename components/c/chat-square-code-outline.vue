<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj-22oqqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fj-22oqqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-code-outline" /></template>
