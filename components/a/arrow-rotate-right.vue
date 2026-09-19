<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxkjz6buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gxkjz6buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-rotate-right" /></template>
