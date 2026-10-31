<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8z4-hb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8z4-hb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:arrow-up" /></template>
