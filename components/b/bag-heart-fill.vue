<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r64ainbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r64ainbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bag-heart-fill" /></template>
