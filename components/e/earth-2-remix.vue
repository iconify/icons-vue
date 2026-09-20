<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mza2qzbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mza2qzbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:earth-2-remix" /></template>
