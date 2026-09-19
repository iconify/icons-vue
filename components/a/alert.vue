<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0w00mqsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="c0w00mqsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:alert" /></template>
