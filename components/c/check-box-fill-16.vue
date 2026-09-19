<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du1gg3oja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="du1gg3oja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-box-fill-16" /></template>
