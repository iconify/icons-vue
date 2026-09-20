<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efm51irty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efm51irty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-up-filled" /></template>
