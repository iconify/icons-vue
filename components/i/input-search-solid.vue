<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxe8wwbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxe8wwbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:input-search-solid" /></template>
