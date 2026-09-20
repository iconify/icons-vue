<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0k-kub9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0k-kub9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:filter-2-solid" /></template>
