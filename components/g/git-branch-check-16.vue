<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_kx0ab8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a_kx0ab8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-branch-check-16" /></template>
