<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3k491x4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3k491x4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:chair-2-solid" /></template>
