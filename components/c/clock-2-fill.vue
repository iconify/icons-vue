<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-hdyqbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-hdyqbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-2-fill" /></template>
