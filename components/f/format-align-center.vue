<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfd6kjw2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="yfd6kjw2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:format-align-center" /></template>
