<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmx2y7bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tmx2y7bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:eyes-look-left" /></template>
