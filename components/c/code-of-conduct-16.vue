<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-od26b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v-od26b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:code-of-conduct-16" /></template>
