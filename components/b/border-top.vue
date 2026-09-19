<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_ka6f25f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r_ka6f25f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:border-top" /></template>
