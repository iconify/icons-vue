<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mojhw-3qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mojhw-3qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:diamond-filled-12" /></template>
