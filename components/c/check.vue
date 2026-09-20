<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1btt3j3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="z1btt3j3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:check" /></template>
