<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3z1ddf_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c3z1ddf_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-check-fill-12" /></template>
