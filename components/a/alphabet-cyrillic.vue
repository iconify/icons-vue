<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxsdz7b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxsdz7b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-cyrillic" /></template>
