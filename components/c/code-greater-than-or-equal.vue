<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di79sqblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di79sqblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code-greater-than-or-equal" /></template>
