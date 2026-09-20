<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h48g7vb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h48g7vb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:box-heart-solid" /></template>
