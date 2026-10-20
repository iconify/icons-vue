<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9h1pi52i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r9h1pi52i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caps-lock-20-bold" /></template>
