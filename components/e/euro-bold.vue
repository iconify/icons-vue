<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfarvkz8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lfarvkz8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:euro-bold" /></template>
