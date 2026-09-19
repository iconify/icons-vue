<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gprqh4byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gprqh4byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-x" /></template>
