<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6l-46h7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k6l-46h7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:adapter-notification" /></template>
