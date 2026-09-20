<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccrfalb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ccrfalb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:garlic-hub-light" /></template>
