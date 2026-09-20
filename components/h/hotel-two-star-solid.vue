<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3nceedcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r3nceedcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hotel-two-star-solid" /></template>
