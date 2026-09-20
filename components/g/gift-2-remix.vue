<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye19x6bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ye19x6bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:gift-2-remix" /></template>
