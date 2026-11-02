<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puanc4qne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puanc4qne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:birthday-2-fill" /></template>
