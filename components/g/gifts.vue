<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi5crlb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="gi5crlb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:gifts" /></template>
