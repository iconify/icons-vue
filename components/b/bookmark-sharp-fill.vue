<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch2api_-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch2api_-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-sharp-fill" /></template>
