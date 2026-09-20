<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp6t2j1op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pp6t2j1op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:eye-16" /></template>
