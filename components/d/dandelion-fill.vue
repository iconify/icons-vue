<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa736sb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa736sb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dandelion-fill" /></template>
