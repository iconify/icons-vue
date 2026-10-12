<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmfq-m5sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dmfq-m5sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bot-message-square-filled" /></template>
