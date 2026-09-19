<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axfkribhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="axfkribhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:book-dead" /></template>
