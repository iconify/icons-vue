<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv5evy_iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cv5evy_iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-plus-16" /></template>
