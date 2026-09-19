<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o942gqbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o942gqbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrows-angle-expand" /></template>
