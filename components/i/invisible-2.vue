<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f44d5db6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="f44d5db6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:invisible-2" /></template>
