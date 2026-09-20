<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmut4uqqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="mmut4uqqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-added" /></template>
