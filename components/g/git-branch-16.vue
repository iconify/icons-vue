<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h98d8zbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h98d8zbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-branch-16" /></template>
