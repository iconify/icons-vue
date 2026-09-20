<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib9lzd7wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ib9lzd7wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-add-outline" /></template>
