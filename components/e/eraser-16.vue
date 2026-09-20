<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okjox9bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="okjox9bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:eraser-16" /></template>
