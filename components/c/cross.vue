<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gobf57txj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gobf57txj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:cross" /></template>
