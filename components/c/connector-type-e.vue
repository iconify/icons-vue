<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p47sh4b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p47sh4b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:connector-type-e" /></template>
