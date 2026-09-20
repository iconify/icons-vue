<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8adt2baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y8adt2baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:dam" /></template>
