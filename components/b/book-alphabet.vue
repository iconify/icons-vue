<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8b-szbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8b-szbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-alphabet" /></template>
