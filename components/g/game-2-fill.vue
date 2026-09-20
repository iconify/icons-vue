<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt4-l-b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt4-l-b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:game-2-fill" /></template>
