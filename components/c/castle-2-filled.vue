<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-ybo53nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-ybo53nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:castle-2-filled" /></template>
