<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvqwwe6ij.css';
import '../../css/g/guc_2ccot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bvqwwe6ij"/><path class="guc_2ccot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:aion" /></template>
