<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q98m4fbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="q98m4fbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:github-text" /></template>
