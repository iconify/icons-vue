<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqraibc5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="tqraibc5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-commit" /></template>
