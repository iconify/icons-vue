<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4ztf7btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="g4ztf7btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:format-vertical-align-center" /></template>
