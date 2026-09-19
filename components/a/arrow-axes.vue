<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpycbh9ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jpycbh9ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-axes" /></template>
