<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he6wivbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="he6wivbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:book-open" /></template>
