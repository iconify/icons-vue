<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztd29dblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ztd29dblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-left-circle-fill" /></template>
