<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-c2tob9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-c2tob9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-outline" /></template>
