<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-uk0zbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g-uk0zbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-ruled" /></template>
