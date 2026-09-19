<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sktsi7btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sktsi7btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:bookmark-slash" /></template>
