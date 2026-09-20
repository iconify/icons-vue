<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brruq5e5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="brruq5e5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:graph-16" /></template>
