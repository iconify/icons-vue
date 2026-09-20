<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugtfc0auw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ugtfc0auw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:drinking-water" /></template>
