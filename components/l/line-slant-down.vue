<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7brm4due.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j7brm4due"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:line-slant-down" /></template>
