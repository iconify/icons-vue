<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnf61wnjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rnf61wnjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:display-dot-matrix-small" /></template>
