<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-i5iccrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y-i5iccrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ice-cream-bowl-filled" /></template>
