<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9c-be7dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f9c-be7dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffin-with-om" /></template>
