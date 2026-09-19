<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7w05_3ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c7w05_3ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:list" /></template>
