<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua6ey7-at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua6ey7-at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:command" /></template>
