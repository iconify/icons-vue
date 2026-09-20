<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-0e6zbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n-0e6zbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:circle-filled" /></template>
