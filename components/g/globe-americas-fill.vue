<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7aa6e__k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v7aa6e__k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:globe-americas-fill" /></template>
