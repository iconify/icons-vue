<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl1uuu-xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl1uuu-xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:checkbox-line" /></template>
