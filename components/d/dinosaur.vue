<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r25x30bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r25x30bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:dinosaur" /></template>
