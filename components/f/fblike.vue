<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebky43byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="ebky43byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fblike" /></template>
