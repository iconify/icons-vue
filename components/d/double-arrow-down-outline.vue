<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kivs9tpmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kivs9tpmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:double-arrow-down-outline" /></template>
