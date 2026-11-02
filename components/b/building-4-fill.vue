<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux3fr-b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux3fr-b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-4-fill" /></template>
