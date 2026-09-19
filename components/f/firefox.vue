<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh516mbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rh516mbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:firefox" /></template>
