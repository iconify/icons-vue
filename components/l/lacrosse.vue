<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alnov8bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="alnov8bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:lacrosse" /></template>
