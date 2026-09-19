<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7z6ubbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h7z6ubbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circles-intersection" /></template>
