<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng7w36b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ng7w36b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:checkbox-intermediate-variant" /></template>
