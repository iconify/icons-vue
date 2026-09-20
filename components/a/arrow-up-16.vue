<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baywupb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="baywupb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-up-16" /></template>
