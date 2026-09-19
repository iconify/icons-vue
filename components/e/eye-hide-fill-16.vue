<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meymu9b3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="meymu9b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:eye-hide-fill-16" /></template>
