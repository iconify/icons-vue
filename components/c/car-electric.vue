<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2y-q-42q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e2y-q-42q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:car-electric" /></template>
