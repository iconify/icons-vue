<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4nhyfskj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d4nhyfskj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:grid-layout-solid" /></template>
