<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfw9dtb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="cfw9dtb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:apps-box" /></template>
