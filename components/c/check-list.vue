<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajvpi2b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajvpi2b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:check-list" /></template>
