<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw4nc3bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw4nc3bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-up-right-fill-round" /></template>
