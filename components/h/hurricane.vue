<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbkj2zr7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mbkj2zr7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hurricane" /></template>
