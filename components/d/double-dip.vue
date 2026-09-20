<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu1zxebkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cu1zxebkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:double-dip" /></template>
