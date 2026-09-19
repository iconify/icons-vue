<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snv3cbbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="snv3cbbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:exclamation-diamond-fill" /></template>
