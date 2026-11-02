<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjxwtnqkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjxwtnqkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aspect-ratio-line" /></template>
