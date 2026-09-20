<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_zf2fb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h_zf2fb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bluetooth-remix" /></template>
