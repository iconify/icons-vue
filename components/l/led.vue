<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onbda0s6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="onbda0s6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:led" /></template>
