<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j31pc0nke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="j31pc0nke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:assignment-return" /></template>
