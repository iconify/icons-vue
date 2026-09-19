<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng-12ub9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ng-12ub9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:build-tool" /></template>
