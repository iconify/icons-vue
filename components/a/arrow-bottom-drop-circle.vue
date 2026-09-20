<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwyhk3bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwyhk3bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-drop-circle" /></template>
