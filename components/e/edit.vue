<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjhq8mbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rjhq8mbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:edit" /></template>
