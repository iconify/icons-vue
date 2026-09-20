<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efbm7bbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="efbm7bbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-added-16" /></template>
