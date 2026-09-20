<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axs8swbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axs8swbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:lock-unlock-4-bold" /></template>
