<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3t86dbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3t86dbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:insert-emoticon" /></template>
