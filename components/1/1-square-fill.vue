<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs_2dcbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bs_2dcbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:1-square-fill" /></template>
