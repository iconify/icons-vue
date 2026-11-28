<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9301-mej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="l9301-mej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-top-thin" /></template>
