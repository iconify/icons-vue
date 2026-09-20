<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w03xylb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w03xylb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:drop" /></template>
