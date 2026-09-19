<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rchyk3jrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rchyk3jrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:git-pull-request" /></template>
