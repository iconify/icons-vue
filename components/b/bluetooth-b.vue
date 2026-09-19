<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qto7n0ozo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1792};
const content = `<path class="qto7n0ozo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:bluetooth-b" /></template>
