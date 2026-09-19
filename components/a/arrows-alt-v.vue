<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5dkcracg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="d5dkcracg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:arrows-alt-v" /></template>
