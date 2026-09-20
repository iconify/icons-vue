<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9v3uqbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f9v3uqbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:golf-tee" /></template>
