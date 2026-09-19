<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c61p-ac-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1792};
const content = `<path class="c61p-ac-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:codiepie" /></template>
