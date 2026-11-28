<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5ms-84tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5ms-84tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:book-open-heart" /></template>
