<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-ijt9znm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u-ijt9znm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-pull-request-draft-16" /></template>
