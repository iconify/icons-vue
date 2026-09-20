<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb3zq7bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb3zq7bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:coreboot" /></template>
