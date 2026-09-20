<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbfkku5pk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbfkku5pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:floor-2" /></template>
