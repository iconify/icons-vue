<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nonu48a3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nonu48a3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:close-fill-round" /></template>
