<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unquf7bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unquf7bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-image-fill" /></template>
