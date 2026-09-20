<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce6a4cb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce6a4cb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:emergency-flashers-fill" /></template>
