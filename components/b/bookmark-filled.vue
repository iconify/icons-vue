<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k98if7bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k98if7bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:bookmark-filled" /></template>
