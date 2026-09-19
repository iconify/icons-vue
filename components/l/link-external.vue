<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obw0lbcts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="obw0lbcts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:link-external" /></template>
