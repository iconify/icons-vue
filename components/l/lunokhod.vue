<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q61l43pac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q61l43pac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:lunokhod" /></template>
