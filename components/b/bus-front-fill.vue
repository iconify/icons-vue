<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8e9ro_ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h8e9ro_ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bus-front-fill" /></template>
