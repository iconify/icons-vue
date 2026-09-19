<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6_zf72ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f6_zf72ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:checkmark" /></template>
