<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jemlzvhwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jemlzvhwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:copy-xmark" /></template>
