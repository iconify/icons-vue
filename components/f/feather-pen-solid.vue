<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqs759a1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zqs759a1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:feather-pen-solid" /></template>
