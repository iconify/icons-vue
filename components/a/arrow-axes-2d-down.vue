<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blah4vbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="blah4vbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-axes-2d-down" /></template>
