<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_wv08buy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="l_wv08buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alert" /></template>
