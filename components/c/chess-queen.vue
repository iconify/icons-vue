<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f78rt7b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f78rt7b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chess-queen" /></template>
