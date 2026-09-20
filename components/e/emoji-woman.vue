<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkpu2fbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkpu2fbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-woman" /></template>
