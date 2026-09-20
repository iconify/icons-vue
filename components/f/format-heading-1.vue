<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxuekebnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxuekebnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-heading-1" /></template>
