<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c76i_ob0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c76i_ob0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bag-plus-fill" /></template>
