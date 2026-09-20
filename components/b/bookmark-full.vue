<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p630u27za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p630u27za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bookmark-full" /></template>
