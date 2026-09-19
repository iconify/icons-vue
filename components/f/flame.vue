<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7u52s0kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g7u52s0kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:flame" /></template>
