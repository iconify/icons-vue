<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr6v161zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr6v161zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-start-vertical" /></template>
