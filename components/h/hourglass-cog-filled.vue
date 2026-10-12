<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa0f-6aya.css';
import '../../css/l/l6ma61byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa0f-6aya"/><path clip-rule="evenodd" class="l6ma61byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hourglass-cog-filled" /></template>
