<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u50hvuzmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u50hvuzmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:level-down-alt-solid" /></template>
